<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v_ej9heil.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="v_ej9heil"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="sidekickicons:section-sign-20-solid" {...props}></Icon>
