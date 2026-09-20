<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l51imkbfp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="l51imkbfp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="picon:shovel" {...props}></Icon>
