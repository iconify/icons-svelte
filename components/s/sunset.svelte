<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/elivbdczw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="elivbdczw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:sunset" {...props}></Icon>
