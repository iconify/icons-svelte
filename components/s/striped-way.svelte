<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m4whe5bzq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="m4whe5bzq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="temaki:striped-way" {...props}></Icon>
