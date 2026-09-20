<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a-idt_63d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="a-idt_63d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-icon-theme:shader" {...props}></Icon>
