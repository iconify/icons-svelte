<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d61kn7vhl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="d61kn7vhl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="andrsrxn:spinner" {...props}></Icon>
