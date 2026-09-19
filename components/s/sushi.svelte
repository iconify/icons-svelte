<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e-61rbjll.css';
import '../../css/l/lo95uel6m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<ellipse class="e-61rbjll"/><path class="lo95uel6m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bxs:sushi" {...props}></Icon>
