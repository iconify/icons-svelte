<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/av9tyjb2g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="av9tyjb2g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:trophy-star-filled" {...props}></Icon>
