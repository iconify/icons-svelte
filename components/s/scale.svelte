<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/im4sm4brc.css';
import '../../css/v/vyso5givu.css';
import '../../css/f/fb1jcdm6g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":100,"height":100};
const content = `<path class="im4sm4brc"/><path class="vyso5givu"/><path class="fb1jcdm6g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gis:scale" {...props}></Icon>
