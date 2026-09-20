<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zmgj_4bpe.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zmgj_4bpe"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:table-border" {...props}></Icon>
