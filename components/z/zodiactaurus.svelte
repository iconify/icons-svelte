<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bvavf9b_l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1025,"height":1024};
const content = `<path class="bvavf9b_l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:zodiactaurus" {...props}></Icon>
