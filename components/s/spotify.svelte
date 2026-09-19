<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jzx9n_blw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="jzx9n_blw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cib:spotify" {...props}></Icon>
