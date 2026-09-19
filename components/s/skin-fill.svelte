<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bar-u5a1j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="bar-u5a1j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ant-design:skin-fill" {...props}></Icon>
