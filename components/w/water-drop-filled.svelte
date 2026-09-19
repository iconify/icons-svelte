<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tf_hh-lha.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="tf_hh-lha"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:water-drop-filled" {...props}></Icon>
