<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q367x2bks.css';
import '../../css/a/ae_9512ms.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="q367x2bks"/><path class="ae_9512ms"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="famicons:tablet-landscape" {...props}></Icon>
