<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q7tndbczd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="q7tndbczd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="sidekickicons:step-forward-16-solid" {...props}></Icon>
