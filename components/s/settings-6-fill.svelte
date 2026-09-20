<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qrf8tpm0o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="qrf8tpm0o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:settings-6-fill" {...props}></Icon>
