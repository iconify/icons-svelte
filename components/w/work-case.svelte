<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vrq4ddb6o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":496};
const content = `<path class="vrq4ddb6o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ps:work-case" {...props}></Icon>
