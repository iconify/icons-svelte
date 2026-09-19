<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/thndgcb3e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="thndgcb3e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ant-design:skype-outlined" {...props}></Icon>
