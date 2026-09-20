<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b0g55ej2c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="b0g55ej2c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:safari" {...props}></Icon>
