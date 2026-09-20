<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jpgbqyjja.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jpgbqyjja"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:stylus" {...props}></Icon>
