<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nabblub0v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="nabblub0v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ant-design:thunderbolt-outline" {...props}></Icon>
