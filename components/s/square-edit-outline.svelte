<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k-5sc1bmq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="k-5sc1bmq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:square-edit-outline" {...props}></Icon>
