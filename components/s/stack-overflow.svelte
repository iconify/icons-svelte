<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nmsje_bdw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":24};
const content = `<path class="nmsje_bdw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fontisto:stack-overflow" {...props}></Icon>
