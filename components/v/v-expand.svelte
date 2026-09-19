<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/eq8js-0ub.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":256};
const content = `<path class="eq8js-0ub"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fad:v-expand" {...props}></Icon>
