<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lkh1ubbwh.css';
import '../../css/n/nzqt12bbz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="lkh1ubbwh"/><path clip-rule="evenodd" class="nzqt12bbz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="qlementine-icons:scanner-16" {...props}></Icon>
