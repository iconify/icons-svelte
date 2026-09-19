<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l0ei_2o1l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="l0ei_2o1l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons-solid:shield-check" {...props}></Icon>
