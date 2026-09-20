<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b-jpj73bt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="b-jpj73bt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="picon:todo" {...props}></Icon>
