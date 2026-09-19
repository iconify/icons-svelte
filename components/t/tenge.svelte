<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qgp4nsy0v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":384,"height":512};
const content = `<path class="qgp4nsy0v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-solid:tenge" {...props}></Icon>
