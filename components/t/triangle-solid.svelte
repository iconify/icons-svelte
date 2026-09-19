<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xvkykw33t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":2048,"height":2048};
const content = `<path class="xvkykw33t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-mdl2:triangle-solid" {...props}></Icon>
