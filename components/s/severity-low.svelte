<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ygepkbb4q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<circle class="ygepkbb4q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pajamas:severity-low" {...props}></Icon>
