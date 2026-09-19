<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uowjoqehi.css';
import '../../css/s/se-m8-fzs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="uowjoqehi"/><path class="se-m8-fzs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:search-plus" {...props}></Icon>
