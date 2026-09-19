<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iio3flbyw.css';
import '../../css/u/u3637ccul.css';
import '../../css/r/rc8bmi5tc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="iio3flbyw"/><circle class="u3637ccul"/><path class="rc8bmi5tc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="circum:warning" {...props}></Icon>
