<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qa4xafn4g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qa4xafn4g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:selection-lasso" {...props}></Icon>
