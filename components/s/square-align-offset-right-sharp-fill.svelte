<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m8t6p8bru.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="m8t6p8bru"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:square-align-offset-right-sharp-fill" {...props}></Icon>
