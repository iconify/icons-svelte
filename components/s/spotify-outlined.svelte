<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pk5wt0bov.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="pk5wt0bov"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ant-design:spotify-outlined" {...props}></Icon>
