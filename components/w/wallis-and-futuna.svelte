<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kkjv3ybyr.css';
import '../../css/z/zc-w15bqg.css';
import '../../css/y/y4kj_7blv.css';
import '../../css/i/ifll36buk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":30,"height":24};
const content = `<path class="kkjv3ybyr"/><path class="zc-w15bqg"/><path class="y4kj_7blv"/><path class="ifll36buk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler-flags:wallis-and-futuna" {...props}></Icon>
