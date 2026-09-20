<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/soaq0qb0v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="soaq0qb0v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:toolbox" {...props}></Icon>
