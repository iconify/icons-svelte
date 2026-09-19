<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vg9j1eb8x.css';
import '../../css/v/v71f_-age.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":100,"height":100};
const content = `<path class="vg9j1eb8x"/><path class="v71f_-age"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="foundation:usb" {...props}></Icon>
