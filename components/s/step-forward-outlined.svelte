<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fh_fhblyw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="fh_fhblyw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ant-design:step-forward-outlined" {...props}></Icon>
