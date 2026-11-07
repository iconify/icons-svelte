<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b15_6um9z.css';
import '../../css/o/o2ipnf05e.css';
import '../../css/o/o53u6goso.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="b15_6um9z"/><path clip-rule="evenodd" class="o2ipnf05e"/><path class="o53u6goso"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:slider-minimalistic-horizontal-outline" {...props}></Icon>
