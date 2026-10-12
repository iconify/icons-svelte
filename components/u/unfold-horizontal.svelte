<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k8334x15o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="k8334x15o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="andrsrxn:unfold-horizontal" {...props}></Icon>
