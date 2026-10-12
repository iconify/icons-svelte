<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kkfscribz.css';
import '../../css/e/epuqqhiuz.css';
import '../../css/b/bis6shb4l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="kkfscribz"/><path class="epuqqhiuz"/><path class="bis6shb4l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:sun-stroke-20" {...props}></Icon>
