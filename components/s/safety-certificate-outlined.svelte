<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hi33acb7x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="hi33acb7x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ant-design:safety-certificate-outlined" {...props}></Icon>
