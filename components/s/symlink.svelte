<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a4zfxlbgj.css';
import '../../css/b/bh79t3b8l.css';
import '../../css/n/nnghyyb1l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="a4zfxlbgj"/><path class="bh79t3b8l"/><path class="nnghyyb1l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="catppuccin:symlink" {...props}></Icon>
