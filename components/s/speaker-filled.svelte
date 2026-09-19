<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w2j9pvdbt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="w2j9pvdbt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:speaker-filled" {...props}></Icon>
