<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lhlsn0baz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="lhlsn0baz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="picon:whale" {...props}></Icon>
