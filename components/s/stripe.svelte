<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bv-xx4z6f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bv-xx4z6f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="grommet-icons:stripe" {...props}></Icon>
