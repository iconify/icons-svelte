<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o4cp7bq3m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="o4cp7bq3m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fe:tablet" {...props}></Icon>
