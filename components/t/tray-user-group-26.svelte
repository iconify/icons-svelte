<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ojleve2qp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":26,"height":26};
const content = `<path class="ojleve2qp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:tray-user-group-26" {...props}></Icon>
