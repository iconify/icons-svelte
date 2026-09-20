<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z--u7bblr.css';
import '../../css/k/kfpic71-k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="z--u7bblr"/><path class="kfpic71-k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="stash:square-check-light" {...props}></Icon>
