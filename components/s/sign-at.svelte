<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lk-jk3b-d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="lk-jk3b-d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-plump:sign-at" {...props}></Icon>
