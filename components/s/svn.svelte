<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/ndxyiq8pj.css';
import '../../css/l/lyhf8fbbo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":33,"height":24};
const content = `<path class="ndxyiq8pj"/><path class="lyhf8fbbo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fontisto:svn" {...props}></Icon>
