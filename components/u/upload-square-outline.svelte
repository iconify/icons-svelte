<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/ao23nccsy.css';
import '../../css/y/ye6llnqhf.css';
import '../../css/m/mzfoi9l1e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ao23nccsy"/><path class="ye6llnqhf"/><path clip-rule="evenodd" class="mzfoi9l1e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:upload-square-outline" {...props}></Icon>
