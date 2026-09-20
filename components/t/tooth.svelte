<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/utegbx69l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="utegbx69l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:tooth" {...props}></Icon>
