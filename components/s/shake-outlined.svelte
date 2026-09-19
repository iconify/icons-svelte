<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/aoz0_bc9u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="aoz0_bc9u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ant-design:shake-outlined" {...props}></Icon>
