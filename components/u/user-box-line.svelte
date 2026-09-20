<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nrj6p8qat.css';
import '../../css/z/zv6cqnbnp.css';
import '../../css/y/ypl1pmbdy.css';
import '../../css/j/jgjjp7t-j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><circle class="zv6cqnbnp"/><path class="ypl1pmbdy"/><rect class="jgjjp7t-j"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="majesticons:user-box-line" {...props}></Icon>
