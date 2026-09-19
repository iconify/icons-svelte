<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gvvot-35f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":750,"height":850};
const content = `<path class="gvvot-35f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="il:world" {...props}></Icon>
