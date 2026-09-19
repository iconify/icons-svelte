<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o8hx9ob2o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="o8hx9ob2o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cib:stackpath" {...props}></Icon>
