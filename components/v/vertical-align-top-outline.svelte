<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q34wt5ikc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="q34wt5ikc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ant-design:vertical-align-top-outline" {...props}></Icon>
