<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/ci_yrdbbn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ci_yrdbbn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-ultimate:swimming-pool-stairs-bold" {...props}></Icon>
