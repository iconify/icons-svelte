<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rthtgrrbd.css';
import '../../css/l/l-i-cfbtp.css';
import '../../css/c/c5c5h6dcw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="rthtgrrbd"/><path class="l-i-cfbtp"/><path class="c5c5h6dcw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:table-48" {...props}></Icon>
