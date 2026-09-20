<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h0dhspbqm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":18,"height":18};
const content = `<path class="h0dhspbqm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="jam:unlink" {...props}></Icon>
