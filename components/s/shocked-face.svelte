<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/ha7yqp6ru.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="ha7yqp6ru"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="at-icons:shocked-face" {...props}></Icon>
