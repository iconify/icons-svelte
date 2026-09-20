<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j2y6teb_s.css';
import '../../css/t/tyddiab8w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="j2y6teb_s"/><path class="tyddiab8w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-pixel:school-science-test-flask" {...props}></Icon>
