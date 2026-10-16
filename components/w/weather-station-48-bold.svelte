<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fixnhbu5f.css';
import '../../css/f/fnpggwb5s.css';
import '../../css/f/f7wkctbah.css';
import '../../css/y/y9zsbtbwi.css';
import '../../css/p/phox42bnd.css';
import '../../css/s/see0y-btr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="fixnhbu5f"/><path class="fnpggwb5s"/><path class="f7wkctbah"/><path class="y9zsbtbwi"/><path class="phox42bnd"/><path class="see0y-btr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:weather-station-48-bold" {...props}></Icon>
