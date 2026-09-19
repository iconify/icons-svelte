<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bcxs87bij.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="bcxs87bij"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ant-design:trademark-circle-fill" {...props}></Icon>
