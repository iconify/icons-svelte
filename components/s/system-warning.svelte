<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sunnwjbfh.css';
import '../../css/k/k6q-kjzhj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="sunnwjbfh"/><path class="k6q-kjzhj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="eos-icons:system-warning" {...props}></Icon>
