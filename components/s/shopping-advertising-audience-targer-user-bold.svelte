<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tg11e7bbh.css';
import '../../css/p/prb4-qbxu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tg11e7bbh"/><path class="prb4-qbxu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-ultimate:shopping-advertising-audience-targer-user-bold" {...props}></Icon>
