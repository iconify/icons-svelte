<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rni7dhh3o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="rni7dhh3o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ant-design:tag-fill" {...props}></Icon>
