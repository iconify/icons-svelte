<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sgig6s6kb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="sgig6s6kb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:square-half-sharp-fill" {...props}></Icon>
