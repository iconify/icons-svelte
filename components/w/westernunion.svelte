<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b8iwk6bgu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="b8iwk6bgu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:westernunion" {...props}></Icon>
