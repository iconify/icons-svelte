<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v11itpgom.css';
import '../../css/b/bwibdw4bb.css';
import '../../css/d/dasv9vo5d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="v11itpgom"/><path class="bwibdw4bb"/><path class="dasv9vo5d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:upside-down" {...props}></Icon>
