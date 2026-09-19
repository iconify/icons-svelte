<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/ayvh8hlxw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ayvh8hlxw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:washing-machine-filled" {...props}></Icon>
