<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ume5d43jk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ume5d43jk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="grommet-icons:storage" {...props}></Icon>
