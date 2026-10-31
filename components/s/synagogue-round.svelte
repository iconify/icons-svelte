<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g9aa3wsrh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="g9aa3wsrh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:synagogue-round" {...props}></Icon>
