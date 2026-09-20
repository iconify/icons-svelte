<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lyijsv-va.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lyijsv-va"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:scikit-learn" {...props}></Icon>
