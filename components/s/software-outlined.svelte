<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t4kc8vb4f.css';
import '../../css/i/ii8qtwyrs.css';
import '../../css/o/on4fre1ek.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="t4kc8vb4f"/><path class="ii8qtwyrs"/><circle class="on4fre1ek"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="eos-icons:software-outlined" {...props}></Icon>
