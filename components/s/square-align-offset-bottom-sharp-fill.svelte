<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w1z6d-bhk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="w1z6d-bhk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:square-align-offset-bottom-sharp-fill" {...props}></Icon>
