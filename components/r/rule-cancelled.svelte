<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s3p-e2bku.css';
import '../../css/r/rrl70bbti.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="s3p-e2bku"/><path class="rrl70bbti"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:rule-cancelled" {...props}></Icon>
