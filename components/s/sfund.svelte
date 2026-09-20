<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c9bg9h1um.css';
import '../../css/t/txkp30byp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="c9bg9h1um"/><path class="txkp30byp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:sfund" {...props}></Icon>
