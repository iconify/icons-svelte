<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rjl_jbb4y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24,"left":-5,"top":-5};
const content = `<path class="rjl_jbb4y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="jam:signal" {...props}></Icon>
