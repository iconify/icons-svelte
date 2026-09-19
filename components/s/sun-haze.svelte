<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uvf9yc10o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":56,"height":56};
const content = `<path class="uvf9yc10o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="f7:sun-haze" {...props}></Icon>
