<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mij9qtw9d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="mij9qtw9d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:tooth-veneer-filled" {...props}></Icon>
