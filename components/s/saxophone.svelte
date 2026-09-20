<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lt13r4bix.css';
import '../../css/g/gw7mb_bdb.css';
import '../../css/b/bnkx5bbkr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":72,"height":72};
const content = `<path class="lt13r4bix"/><path class="gw7mb_bdb"/><path class="bnkx5bbkr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="openmoji:saxophone" {...props}></Icon>
