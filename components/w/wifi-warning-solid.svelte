<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bxznp3bar.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="bxznp3bar"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoir:wifi-warning-solid" {...props}></Icon>
