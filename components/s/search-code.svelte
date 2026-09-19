<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q1rtdfb3c.css';
import '../../css/u/uowjoqehi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="q1rtdfb3c"/><path class="uowjoqehi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:search-code" {...props}></Icon>
