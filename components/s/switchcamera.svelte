<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o1tq20b9i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":26,"height":26};
const content = `<path class="o1tq20b9i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="wpf:switchcamera" {...props}></Icon>
