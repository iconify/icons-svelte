<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k-hm_lb3s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="k-hm_lb3s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dinkie-icons:sina-weibo" {...props}></Icon>
