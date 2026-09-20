<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k9_mc5n2b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="k9_mc5n2b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="majesticons:text-wrap-line" {...props}></Icon>
