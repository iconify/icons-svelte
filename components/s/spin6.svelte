<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mycp4-b_f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1000,"height":1000};
const content = `<path class="fil0 mycp4-b_f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fontelico:spin6" {...props}></Icon>
