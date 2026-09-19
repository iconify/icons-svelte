<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b-u-z0bcd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="b-u-z0bcd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ant-design:safety-certificate-fill" {...props}></Icon>
