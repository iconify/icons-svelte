<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bq1ywbbug.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bq1ywbbug"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:up-arrow-alt" {...props}></Icon>
