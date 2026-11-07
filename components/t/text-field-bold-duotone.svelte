<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/et59vtbnu.css';
import '../../css/t/tmd21lv3k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="et59vtbnu"/><path class="tmd21lv3k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:text-field-bold-duotone" {...props}></Icon>
