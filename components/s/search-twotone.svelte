<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iw1iew.css';
import '../../css/q/qf4zap.css';
import '../../css/o/o5a9uc.css';
import '../../css/f/fill-to-0.css';
import '../../css/s/so-from-40.css';
import '../../css/f/fill-to-0_3.css';
import '../../css/s/so-to-0.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="iw1iew qf4zap"/><path class="iw1iew o5a9uc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="line-md:search-twotone" {...props}></Icon>
