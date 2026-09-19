<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hkjh_uz7x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="hkjh_uz7x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:surrounded-eye" {...props}></Icon>
