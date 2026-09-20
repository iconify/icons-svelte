<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r9f3l-bvc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="r9f3l-bvc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:wyze" {...props}></Icon>
