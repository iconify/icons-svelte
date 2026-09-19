<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k8p1fxbgk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="k8p1fxbgk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:shapes-alt-2" {...props}></Icon>
