<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lpiua4svc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lpiua4svc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide:strikethrough" {...props}></Icon>
