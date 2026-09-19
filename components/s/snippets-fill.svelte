<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o17-5bbuc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="o17-5bbuc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ant-design:snippets-fill" {...props}></Icon>
