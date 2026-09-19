<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lx5jx9gaq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="lx5jx9gaq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cib:snyk" {...props}></Icon>
