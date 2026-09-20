<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mlr6ijy8o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="mlr6ijy8o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:webpack-solid" {...props}></Icon>
