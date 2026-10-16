<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/etp81e8xx.css';
import '../../css/s/smtmkz67c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="etp81e8xx"/><path class="smtmkz67c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:scrubber-20-bold" {...props}></Icon>
