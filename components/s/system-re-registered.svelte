<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sugy9id7y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="sugy9id7y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="eos-icons:system-re-registered" {...props}></Icon>
