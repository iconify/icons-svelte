<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oz6-5w-0c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="oz6-5w-0c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ant-design:setting-outline" {...props}></Icon>
