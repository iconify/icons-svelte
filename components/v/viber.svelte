<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kzb7f3prz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kzb7f3prz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:viber" {...props}></Icon>
