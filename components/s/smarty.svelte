<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lnxku9bqq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="lnxku9bqq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-icon-theme:smarty" {...props}></Icon>
