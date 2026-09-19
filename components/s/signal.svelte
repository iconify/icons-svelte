<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nkns7hbep.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="nkns7hbep"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ant-design:signal" {...props}></Icon>
