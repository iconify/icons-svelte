<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/te2je-_dw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="te2je-_dw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="entypo:v-card" {...props}></Icon>
