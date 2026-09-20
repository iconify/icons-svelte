<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v8zvaacbm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="v8zvaacbm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pajamas:severity-critical" {...props}></Icon>
